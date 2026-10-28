<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/g/g-o6a2-ay.css';
import '../../css/l/lor0dobsk.css';
import '../../css/u/u91wj2bhd.css';
import '../../css/y/ywomxlbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="g-o6a2-ay"/><rect class="lor0dobsk"/><rect class="u91wj2bhd"/><circle class="ywomxlbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:application" /></template>
