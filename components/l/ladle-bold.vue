<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7zq275ci.css';
import '../../css/f/fzcjrqbtu.css';
import '../../css/t/tg66l2b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7zq275ci"/><path class="fzcjrqbtu"/><path class="tg66l2b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ladle-bold" /></template>
