<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ijwbgek4s.css';
import '../../css/w/w1fn0ab-e.css';
import '../../css/r/r6k29b9ku.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/p/pckaxha-v.css';
import '../../css/y/y_s7vvbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ijwbgek4s"/><path class="w1fn0ab-e"/><path class="r6k29b9ku"/><circle class="h_tsn8bxt"/><path class="pckaxha-v"/><path class="y_s7vvbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-scan-broken" /></template>
