<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3vgmfb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="c3vgmfb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:liquor-store" /></template>
