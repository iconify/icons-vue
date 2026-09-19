<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axw8mbbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="axw8mbbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-uturn-down-right" /></template>
