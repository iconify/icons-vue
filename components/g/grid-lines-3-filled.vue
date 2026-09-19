<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em465ibab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em465ibab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-lines-3-filled" /></template>
