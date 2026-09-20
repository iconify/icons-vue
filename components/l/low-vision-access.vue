<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhs7z7x8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="lhs7z7x8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:low-vision-access" /></template>
