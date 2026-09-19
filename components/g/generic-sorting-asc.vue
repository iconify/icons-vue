<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al-qozjuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="al-qozjuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:generic-sorting-asc" /></template>
