<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/oi83abcqf.css';
import '../../css/w/wqmtzgbbi.css';
import '../../css/e/e-rh4-bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="oi83abcqf"/><path class="wqmtzgbbi"/><path class="e-rh4-bqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:instagram-logo-1" /></template>
