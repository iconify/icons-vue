<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnx8k-b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnx8k-b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:filter-check" /></template>
