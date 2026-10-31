<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dia1yf76r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dia1yf76r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-check-fill-round" /></template>
