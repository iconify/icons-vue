<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4coe1bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n4coe1bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-left-48-bold" /></template>
