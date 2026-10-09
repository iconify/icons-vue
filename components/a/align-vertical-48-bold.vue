<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wupjjnqjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wupjjnqjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-vertical-48-bold" /></template>
