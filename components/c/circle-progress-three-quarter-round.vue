<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyu1pxbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyu1pxbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-three-quarter-round" /></template>
