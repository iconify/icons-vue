<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lom6tkt7o.css';
import '../../css/e/exw8c4mtv.css';
import '../../css/p/pzgcelb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lom6tkt7o"/><path class="exw8c4mtv"/><path class="pzgcelb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dua" /></template>
