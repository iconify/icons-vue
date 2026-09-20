<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rwzkv6b2g.css';
import '../../css/u/uqhik9b3f.css';
import '../../css/d/d-03ckbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rwzkv6b2g"/><path class="uqhik9b3f"/><path class="d-03ckbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:history-2-broken" /></template>
