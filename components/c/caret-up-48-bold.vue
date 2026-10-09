<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/javl4uyul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="javl4uyul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-up-48-bold" /></template>
