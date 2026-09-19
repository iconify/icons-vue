<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/p2qes6yjx.css';
import '../../css/z/zwzneibzu.css';
import '../../css/c/c85xlhb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="p2qes6yjx"/><path class="zwzneibzu"/><path class="c85xlhb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:increase" /></template>
