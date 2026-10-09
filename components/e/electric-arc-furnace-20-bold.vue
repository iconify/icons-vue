<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smlwvlmfy.css';
import '../../css/n/ntge0rvwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="smlwvlmfy"/><path class="ntge0rvwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-arc-furnace-20-bold" /></template>
