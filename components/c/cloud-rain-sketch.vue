<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y7u8bnbya.css';
import '../../css/y/ytq3-rb7s.css';
import '../../css/k/k1axlacgx.css';
import '../../css/e/ene1tmkdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y7u8bnbya"/><path class="wm-a ytq3-rb7s"/><path class="k1axlacgx wm-k"/><path class="ene1tmkdl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-rain-sketch" /></template>
