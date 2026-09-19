<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulvg8qbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulvg8qbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diff" /></template>
