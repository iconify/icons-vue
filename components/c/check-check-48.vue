<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhb3nmbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hhb3nmbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-check-48" /></template>
