<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvzui74pn.css';
import '../../css/u/uxmtnwu0t.css';
import '../../css/r/rb9owibwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvzui74pn"/><path class="uxmtnwu0t"/><path class="rb9owibwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loan-48-bold" /></template>
