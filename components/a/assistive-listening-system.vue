<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3l1kjaet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="x3l1kjaet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:assistive-listening-system" /></template>
