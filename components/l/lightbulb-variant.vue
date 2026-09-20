<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw4srlbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw4srlbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-variant" /></template>
