<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwfgn5qgs.css';
import '../../css/q/qa0e82m0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwfgn5qgs"/><path class="qa0e82m0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-joint-20-bold" /></template>
