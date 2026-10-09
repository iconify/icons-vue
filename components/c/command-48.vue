<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u52m7xbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u52m7xbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:command-48" /></template>
