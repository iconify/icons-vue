<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1_sbqmea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t1_sbqmea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-underline" /></template>
