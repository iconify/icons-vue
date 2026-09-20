<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqr7tyqju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zqr7tyqju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-d" /></template>
