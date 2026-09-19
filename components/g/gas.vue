<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/u/u-8kx8qao.css';
import '../../css/t/t2t87mb4v.css';
import '../../css/c/c93p4rrcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="u-8kx8qao"/><path class="t2t87mb4v"/><path class="c93p4rrcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:gas" /></template>
