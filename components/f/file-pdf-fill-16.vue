<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru8mpqtzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ru8mpqtzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-pdf-fill-16" /></template>
