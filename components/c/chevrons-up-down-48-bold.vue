<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma2qfxbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ma2qfxbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-down-48-bold" /></template>
