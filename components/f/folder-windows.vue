<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_ztdbjh.css';
import '../../css/p/pnudnz5ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ru_ztdbjh"/><path class="pnudnz5ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-windows" /></template>
