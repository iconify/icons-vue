<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfttfe_2y.css';
import '../../css/k/kvn-2v0wt.css';
import '../../css/u/uj7ng7b-o.css';
import '../../css/v/vmxx54baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="kvn-2v0wt"/><path class="uj7ng7b-o"/><path class="vmxx54baz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:bash" /></template>
