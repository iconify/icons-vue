<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxcl3kb-l.css';
import '../../css/y/y-7_m5bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxcl3kb-l"/><path class="y-7_m5bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-generate" /></template>
