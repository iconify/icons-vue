<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwfwz154d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwfwz154d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-floor-zero" /></template>
