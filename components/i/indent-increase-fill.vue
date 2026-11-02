<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8-cp0bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8-cp0bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:indent-increase-fill" /></template>
