<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajtnjnklx.css';
import '../../css/s/sb9rsi1bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ajtnjnklx"/><path class="sb9rsi1bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frying-pan-48" /></template>
