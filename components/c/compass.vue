<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/baen2yhxr.css';
import '../../css/o/opyzyd53f.css';
import '../../css/n/neptv8bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="baen2yhxr"/><circle class="opyzyd53f"/><path class="neptv8bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:compass" /></template>
