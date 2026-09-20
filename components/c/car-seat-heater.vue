<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s75y5vt7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s75y5vt7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-seat-heater" /></template>
