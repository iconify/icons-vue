<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wms6fp07h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wms6fp07h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chart-increasing" /></template>
