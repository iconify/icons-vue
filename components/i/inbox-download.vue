<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mlkrqcdzy.css';
import '../../css/l/lkirl3btc.css';
import '../../css/o/opbqqrbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="mlkrqcdzy"/><path class="lkirl3btc"/><path class="opbqqrbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:inbox-download" /></template>
