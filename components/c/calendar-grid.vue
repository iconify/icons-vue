<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igc--_p_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igc--_p_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-grid" /></template>
