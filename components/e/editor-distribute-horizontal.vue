<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-wk-pbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-wk-pbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-distribute-horizontal" /></template>
