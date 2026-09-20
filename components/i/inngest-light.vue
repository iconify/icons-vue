<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhuwacq1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":30};
const content = `<path clip-rule="evenodd" class="nhuwacq1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inngest-light" /></template>
