<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwg_unjmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vwg_unjmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:aztec-calendar-sun" /></template>
