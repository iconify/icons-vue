<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsdao61r.css';
import '../../css/i/iip0rz5nl.css';
import '../../css/o/oqq-bg_3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="iip0rz5nl"/><path class="oqq-bg_3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:dart" /></template>
