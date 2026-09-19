<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr3r1xpmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yr3r1xpmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-spreadsheet" /></template>
