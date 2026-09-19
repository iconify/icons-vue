<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tygts_5js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tygts_5js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:audio-description" /></template>
