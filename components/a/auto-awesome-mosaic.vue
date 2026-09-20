<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0lf81_ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0lf81_ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:auto-awesome-mosaic" /></template>
