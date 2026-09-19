<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkki8g2_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkki8g2_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:car-front" /></template>
