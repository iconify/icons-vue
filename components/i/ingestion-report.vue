<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew969ac-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ew969ac-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ingestion-report" /></template>
