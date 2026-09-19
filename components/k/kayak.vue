<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l_b5ckbap.css';
import '../../css/z/zo6arnkly.css';
import '../../css/e/eo2tmu8cn.css';
import '../../css/f/fr8pgfmxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="l_b5ckbap"/><path clip-rule="evenodd" class="zo6arnkly"/><path class="eo2tmu8cn"/><path class="fr8pgfmxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:kayak" /></template>
