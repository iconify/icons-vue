<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehr5pjbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehr5pjbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-spreadsheet-x" /></template>
