<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/msg0u7sde.css';
import '../../css/y/y6mx4_bvf.css';
import '../../css/u/uqhik9b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="msg0u7sde"/><path class="y6mx4_bvf"/><path class="uqhik9b3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:history-3-broken" /></template>
