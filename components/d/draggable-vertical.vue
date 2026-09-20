<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx4qkwd-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cx4qkwd-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:draggable-vertical" /></template>
