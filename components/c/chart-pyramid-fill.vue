<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbo9cf8pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbo9cf8pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pyramid-fill" /></template>
