<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mo08gcb_w.css';
import '../../css/t/tgtr_43fx.css';
import '../../css/r/r7x2ymb7x.css';
import '../../css/s/s2a48dbdz.css';
import '../../css/k/kvicmu0no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mo08gcb_w"/><path class="tgtr_43fx"/><path class="r7x2ymb7x"/><path class="s2a48dbdz"/><path class="kvicmu0no"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-linear" /></template>
