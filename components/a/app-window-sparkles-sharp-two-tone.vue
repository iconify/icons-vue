<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kjptfrbkg.css';
import '../../css/h/h6p02wb4t.css';
import '../../css/o/omi2j1bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kjptfrbkg"/><path class="h6p02wb4t"/><path class="omi2j1bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-sparkles-sharp-two-tone" /></template>
