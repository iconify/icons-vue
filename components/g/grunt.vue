<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysj_5aczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ysj_5aczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:grunt" /></template>
