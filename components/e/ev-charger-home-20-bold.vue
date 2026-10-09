<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awwur6tzl.css';
import '../../css/l/l9ao81bdv.css';
import '../../css/x/xfmnipbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="awwur6tzl"/><path class="l9ao81bdv"/><path class="xfmnipbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-home-20-bold" /></template>
