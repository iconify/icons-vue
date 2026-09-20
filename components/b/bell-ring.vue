<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwrnt-b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwrnt-b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bell-ring" /></template>
