<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m81sh779s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m81sh779s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-ordered-48" /></template>
