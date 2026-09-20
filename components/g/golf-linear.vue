<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k7b4fo5xh.css';
import '../../css/y/ya4v2ogmm.css';
import '../../css/h/hzret1bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><ellipse class="k7b4fo5xh"/><path class="ya4v2ogmm"/><path class="hzret1bgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-linear" /></template>
