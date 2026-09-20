<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecu067-ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="ecu067-ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:file-csv" /></template>
