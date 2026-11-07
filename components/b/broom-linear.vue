<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wi1qbk5_i.css';
import '../../css/k/kt6370brf.css';
import '../../css/b/bvwkol5hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wi1qbk5_i"/><path class="kt6370brf"/><path class="bvwkol5hk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:broom-linear" /></template>
