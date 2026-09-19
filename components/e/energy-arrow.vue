<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_ey53f3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_ey53f3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:energy-arrow" /></template>
