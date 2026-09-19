<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhb8c01ug.css';
import '../../css/l/lumab6baq.css';
import '../../css/t/tng64wbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="lumab6baq"/><path class="tng64wbcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:lisp" /></template>
