<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th9y1yc-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="th9y1yc-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:ice-fishing" /></template>
