<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh2lvo64r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wh2lvo64r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ai-sparkle-48" /></template>
