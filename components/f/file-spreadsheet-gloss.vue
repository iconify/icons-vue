<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi493krga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi493krga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-spreadsheet-gloss" /></template>
