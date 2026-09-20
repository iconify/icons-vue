<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d7egxzbrr.css';
import '../../css/t/tnfby2q5d.css';
import '../../css/n/na80fjbih.css';
import '../../css/b/by8lpqc5r.css';
import '../../css/p/p6o9-vebo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d7egxzbrr"/><path class="tnfby2q5d"/><path class="na80fjbih"/><path class="by8lpqc5r"/><path class="p6o9-vebo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-full-minimalistic-broken" /></template>
