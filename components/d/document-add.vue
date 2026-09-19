<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyxl8dbgf.css';
import '../../css/b/buduld4sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uyxl8dbgf"/><path class="buduld4sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-add" /></template>
