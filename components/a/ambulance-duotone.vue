<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xt4bdptou.css';
import '../../css/j/j-na3ub7o.css';
import '../../css/h/hc_zcwc_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xt4bdptou"/><path class="j-na3ub7o"/><path class="hc_zcwc_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ambulance-duotone" /></template>
