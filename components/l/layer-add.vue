<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mlyjx9xfn.css';
import '../../css/n/nj96_stqd.css';
import '../../css/s/swblvjb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mlyjx9xfn"/><path class="nj96_stqd"/><path class="swblvjb1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layer-add" /></template>
