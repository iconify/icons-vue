<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfttfe_2y.css';
import '../../css/l/leakr4_1e.css';
import '../../css/f/fudu618jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="leakr4_1e"/><path class="fudu618jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cypress" /></template>
