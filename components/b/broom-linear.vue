<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/ji7z9becj.css';
import '../../css/k/kt6370brf.css';
import '../../css/p/p7xp9ghjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ji7z9becj"/><path class="kt6370brf"/><path class="p7xp9ghjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:broom-linear" /></template>
