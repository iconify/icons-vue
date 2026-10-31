<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8nyf9k4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8nyf9k4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:baseball-round" /></template>
