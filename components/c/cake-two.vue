<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/i/ih_4ne4_y.css';
import '../../css/v/v8blxvper.css';
import '../../css/t/tjvl0_bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="ih_4ne4_y"/><path class="v8blxvper"/><path class="tjvl0_bwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cake-two" /></template>
