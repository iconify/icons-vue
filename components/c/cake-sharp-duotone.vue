<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/hz78iv51y.css';
import '../../css/x/x2kte-byy.css';
import '../../css/q/qj43urbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hz78iv51y"/><path class="x2kte-byy"/><path class="qj43urbvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cake-sharp-duotone" /></template>
