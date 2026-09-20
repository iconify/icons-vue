<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rtlatxgqd.css';
import '../../css/m/mzwrmz51p.css';
import '../../css/v/vg3q4ac4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rtlatxgqd"/><path class="mzwrmz51p"/><path class="vg3q4ac4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fingerprint" /></template>
