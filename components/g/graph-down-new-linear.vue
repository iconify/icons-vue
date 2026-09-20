<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/ley58n3yy.css';
import '../../css/r/r31eezbqv.css';
import '../../css/u/u00ey8bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ley58n3yy"/><path class="r31eezbqv"/><circle class="u00ey8bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-down-new-linear" /></template>
