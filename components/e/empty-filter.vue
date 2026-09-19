<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq32jab3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sq32jab3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:empty-filter" /></template>
