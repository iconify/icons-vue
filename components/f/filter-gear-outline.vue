<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy4myc37i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy4myc37i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filter-gear-outline" /></template>
