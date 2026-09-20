<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vukznrbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vukznrbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bolnisi-cross" /></template>
