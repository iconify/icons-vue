<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2_uhcczz.css';
import '../../css/v/vg640qbkh.css';
import '../../css/t/te1q42bfr.css';
import '../../css/q/q9o-nccri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p2_uhcczz"/><path class="vg640qbkh"/><path class="te1q42bfr"/><path class="q9o-nccri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-bus-20-bold" /></template>
