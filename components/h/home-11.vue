<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/t0e5e1bzb.css';
import '../../css/k/k3vkrebco.css';
import '../../css/y/y5d_3bbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0e5e1bzb"/><path class="k3vkrebco"/><path class="y5d_3bbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:home-11" /></template>
