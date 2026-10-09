<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfezx0bem.css';
import '../../css/a/a1563zsfw.css';
import '../../css/s/s00ny_50k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hfezx0bem"/><path class="a1563zsfw"/><path class="s00ny_50k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-scooter-20" /></template>
