<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv64nmb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="iv64nmb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:jewelry-store" /></template>
