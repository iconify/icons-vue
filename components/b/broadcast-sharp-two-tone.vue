<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jszxh1b0i.css';
import '../../css/x/xrsgy2bxo.css';
import '../../css/f/f7d702b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jszxh1b0i"/><path class="xrsgy2bxo"/><path class="f7d702b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:broadcast-sharp-two-tone" /></template>
