<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m1a0v8b1i.css';
import '../../css/f/ffvukwp6p.css';
import '../../css/t/t8k39sbmk.css';
import '../../css/b/bv16y576p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m1a0v8b1i"/><path class="ffvukwp6p"/><path class="t8k39sbmk"/><path class="bv16y576p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-5-broken" /></template>
