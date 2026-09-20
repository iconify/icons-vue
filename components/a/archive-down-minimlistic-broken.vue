<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cmvazjgux.css';
import '../../css/t/t6vi4ublf.css';
import '../../css/l/lz7dz2q5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cmvazjgux"/><path class="t6vi4ublf"/><path class="lz7dz2q5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-minimlistic-broken" /></template>
