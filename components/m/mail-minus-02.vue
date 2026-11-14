<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e6tif6bqs.css';
import '../../css/r/rj_bktros.css';
import '../../css/d/ddf0atlim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e6tif6bqs"/><path class="rj_bktros"/><path class="ddf0atlim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-minus-02" /></template>
