<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nd4r1gbgv.css';
import '../../css/a/ar0r6f66r.css';
import '../../css/m/mpixi68ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nd4r1gbgv"/><path class="ar0r6f66r wm-a"/><path class="mpixi68ce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:landmark-duo" /></template>
