<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5xjktb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u5xjktb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-generic-stroke-16" /></template>
