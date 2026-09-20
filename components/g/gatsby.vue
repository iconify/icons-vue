<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ralofz4_e.css';
import '../../css/k/ke769lv4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ralofz4_e"/><path class="ke769lv4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gatsby" /></template>
