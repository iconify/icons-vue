<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/f769viv2h.css';
import '../../css/c/c6upwkbge.css';
import '../../css/o/ootzhpboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f769viv2h"/><path class="c6upwkbge"/><path class="ootzhpboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-sparkles-sharp-duotone" /></template>
