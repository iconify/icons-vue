<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ojqs_tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="u6ojqs_tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-spreadsheet-26" /></template>
