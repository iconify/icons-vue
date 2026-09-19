<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb3z14vnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3z14vnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:escalator-down-arrow" /></template>
