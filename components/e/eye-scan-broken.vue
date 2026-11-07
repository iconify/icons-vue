<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ijwbgek4s.css';
import '../../css/w/w1fn0ab-e.css';
import '../../css/y/ym5pocbnu.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/v/vdsubobiu.css';
import '../../css/q/q9pwgx9_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ijwbgek4s"/><path class="w1fn0ab-e"/><path class="ym5pocbnu"/><circle class="h_tsn8bxt"/><path class="vdsubobiu"/><path class="q9pwgx9_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-scan-broken" /></template>
