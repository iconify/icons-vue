<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w0d5lhbyf.css';
import '../../css/x/x7a19qb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w0d5lhbyf"/><path class="x7a19qb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-2-sparkles-sharp" /></template>
