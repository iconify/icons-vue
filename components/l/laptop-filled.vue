<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzh5qzj1y.css';
import '../../css/k/knqltxb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="bzh5qzj1y"/><path class="knqltxb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laptop-filled" /></template>
