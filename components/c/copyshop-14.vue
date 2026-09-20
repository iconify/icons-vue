<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u__94wbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u__94wbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:copyshop-14" /></template>
