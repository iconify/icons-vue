<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqgar4bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqgar4bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:line-v" /></template>
