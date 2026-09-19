<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mt34s3bhs.css';
import '../../css/v/vig5ljzia.css';
import '../../css/d/dm66__bjg.css';
import '../../css/b/bvfbpgyzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mt34s3bhs"/><path class="vig5ljzia"/><path class="dm66__bjg"/><path class="bvfbpgyzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:alarm-clock-duo" /></template>
