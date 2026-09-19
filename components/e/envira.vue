<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sybq1bblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="sybq1bblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:envira" /></template>
