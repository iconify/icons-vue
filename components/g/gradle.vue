<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsdao61r.css';
import '../../css/j/j-h21xgaa.css';
import '../../css/o/osrapabyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="j-h21xgaa"/><path class="osrapabyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:gradle" /></template>
