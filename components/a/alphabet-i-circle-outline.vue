<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt6788bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt6788bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-i-circle-outline" /></template>
