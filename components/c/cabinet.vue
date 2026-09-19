<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t0am5dblx.css';
import '../../css/x/x6-4_dbkf.css';
import '../../css/u/uu9hmksll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="t0am5dblx"/><path class="x6-4_dbkf"/><path class="uu9hmksll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cabinet" /></template>
