<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9b4hcc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e9b4hcc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-ordered-20" /></template>
