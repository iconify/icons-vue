<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrailb4ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrailb4ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-k" /></template>
