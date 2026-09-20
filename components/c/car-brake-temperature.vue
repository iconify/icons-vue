<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h40y5cb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h40y5cb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-brake-temperature" /></template>
