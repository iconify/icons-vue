<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tffwhr94y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tffwhr94y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-arrows-vertical" /></template>
