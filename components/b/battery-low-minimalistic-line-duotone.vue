<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m4dmr2b-x.css';
import '../../css/n/na80fjbih.css';
import '../../css/t/tnfby2q5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m4dmr2b-x"/><path class="na80fjbih"/><path class="tnfby2q5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-low-minimalistic-line-duotone" /></template>
