<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0fsgfb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0fsgfb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-table" /></template>
