<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gjdjfffgs.css';
import '../../css/t/tb1aqpa-v.css';
import '../../css/b/brt3ujb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="gjdjfffgs"/><path class="tb1aqpa-v"/><path class="brt3ujb3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:heart-plus" /></template>
