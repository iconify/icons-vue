<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyf0942nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyf0942nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-swipe-down" /></template>
