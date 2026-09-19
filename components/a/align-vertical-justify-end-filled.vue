<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0si7bc9c.css';
import '../../css/c/c7ja4vb8i.css';
import '../../css/k/knqltxb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="m0si7bc9c"/><rect class="c7ja4vb8i"/><path class="knqltxb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-vertical-justify-end-filled" /></template>
