<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfzn5_bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfzn5_bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-quarter-fill-round" /></template>
