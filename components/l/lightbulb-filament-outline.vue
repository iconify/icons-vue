<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsd-ij4-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsd-ij4-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-filament-outline" /></template>
