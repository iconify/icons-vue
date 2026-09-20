<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qom5ixbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qom5ixbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-circles-communities" /></template>
