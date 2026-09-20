<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdkgl-bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zdkgl-bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:double-chevron-end-rtl" /></template>
