<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io9vencun.css';
import '../../css/z/z9lj_eqfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="io9vencun"/><path class="z9lj_eqfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:candle-20" /></template>
