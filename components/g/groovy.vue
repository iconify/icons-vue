<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsdao61r.css';
import '../../css/o/o0bilwbsi.css';
import '../../css/r/rlsf7gb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="o0bilwbsi"/><path class="rlsf7gb6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:groovy" /></template>
