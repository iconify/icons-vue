<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfttfe_2y.css';
import '../../css/j/jcoe6mbmz.css';
import '../../css/m/mmo_ywq2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="jcoe6mbmz"/><path class="mmo_ywq2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:django" /></template>
