<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m47rgvb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m47rgvb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-csv" /></template>
