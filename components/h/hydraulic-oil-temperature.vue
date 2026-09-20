<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-q_h0b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-q_h0b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hydraulic-oil-temperature" /></template>
