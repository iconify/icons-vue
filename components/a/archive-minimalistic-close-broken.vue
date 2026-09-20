<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t6qgw5b9f.css';
import '../../css/p/p5qbbdc2d.css';
import '../../css/e/e1dpahbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t6qgw5b9f"/><path class="p5qbbdc2d"/><path class="e1dpahbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-minimalistic-close-broken" /></template>
