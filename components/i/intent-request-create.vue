<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyxl8dbgf.css';
import '../../css/a/arfms3bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uyxl8dbgf"/><path class="arfms3bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intent-request-create" /></template>
