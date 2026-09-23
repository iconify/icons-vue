<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/im8wmac8f.css';
import '../../css/i/ij6ehrbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="im8wmac8f"/><path class="ij6ehrbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-trending-up-sparkles-sharp" /></template>
