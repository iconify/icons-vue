<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0axupq2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0axupq2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-arrow-down" /></template>
