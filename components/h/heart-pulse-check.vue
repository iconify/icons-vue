<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egh4vqbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egh4vqbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heart-pulse-check" /></template>
