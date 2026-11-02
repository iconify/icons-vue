<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um7mmebks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um7mmebks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copper-coin-line" /></template>
