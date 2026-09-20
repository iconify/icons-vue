<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn74o912v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn74o912v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-v-box-outline" /></template>
