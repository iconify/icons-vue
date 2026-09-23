<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/bhj_ifbwh.css';
import '../../css/f/flz8mqbuo.css';
import '../../css/v/vura0hvqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bhj_ifbwh"/><path class="flz8mqbuo"/><path class="vura0hvqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-sparkles-sharp-duotone" /></template>
