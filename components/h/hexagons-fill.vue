<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhgi928af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhgi928af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagons-fill" /></template>
