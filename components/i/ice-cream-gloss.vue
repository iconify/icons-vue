<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwp9_9bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwp9_9bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ice-cream-gloss" /></template>
