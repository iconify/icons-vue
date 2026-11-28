<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp13cjb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp13cjb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-spreadsheet-check" /></template>
