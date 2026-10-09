<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i700qdb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i700qdb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brackets-48-bold" /></template>
