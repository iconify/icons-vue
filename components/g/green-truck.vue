<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pdp5dobft.css';
import '../../css/m/m9oyuabbp.css';
import '../../css/w/wr6g3jo2n.css';
import '../../css/y/yu4vwwb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pdp5dobft"/><path class="m9oyuabbp"/><path class="wr6g3jo2n"/><path class="yu4vwwb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:green-truck" /></template>
