<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wc06j3b0v.css';
import '../../css/p/px2iteb1w.css';
import '../../css/f/f5jrq-big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wc06j3b0v"/><path class="px2iteb1w"/><path class="f5jrq-big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:camera-bitcoin" /></template>
