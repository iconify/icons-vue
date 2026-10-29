<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ea8z-ybmv.css';
import '../../css/i/ievz6-bgp.css';
import '../../css/k/k6dkddbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ea8z-ybmv"/><path class="ievz6-bgp wm-a"/><path class="k6dkddbtm wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:holi-splash" /></template>
