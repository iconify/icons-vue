<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbb-tygif.css';
import '../../css/i/iry5se_sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bbb-tygif"/><path class="iry5se_sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:download-cloud-48-bold" /></template>
