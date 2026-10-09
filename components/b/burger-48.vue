<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flkoy18ai.css';
import '../../css/h/h0fs14upu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="flkoy18ai"/><path class="h0fs14upu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:burger-48" /></template>
