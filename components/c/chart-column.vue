<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unkafc4eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unkafc4eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-column" /></template>
