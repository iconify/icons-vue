<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bbtmgmbdx.css';
import '../../css/i/i5hnbmgxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="bbtmgmbdx"/><path clip-rule="evenodd" class="i5hnbmgxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-round-x14-outline" /></template>
