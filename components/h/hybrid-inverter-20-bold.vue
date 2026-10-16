<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqy4zebrn.css';
import '../../css/s/sv9da_bvv.css';
import '../../css/o/oybwn4bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vqy4zebrn"/><path class="sv9da_bvv"/><path class="oybwn4bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hybrid-inverter-20-bold" /></template>
