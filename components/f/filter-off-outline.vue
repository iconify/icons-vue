<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyoxtgb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyoxtgb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filter-off-outline" /></template>
