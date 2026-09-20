<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd0-3ctca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd0-3ctca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:low-beam-headlights-fill" /></template>
