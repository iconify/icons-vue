<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/za5n-1h_v.css';
import '../../css/s/srg9fvpxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="za5n-1h_v"/><path class="srg9fvpxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lightbulb-sparkles-sharp-fill" /></template>
