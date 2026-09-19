<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mskz4lbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mskz4lbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kaggle" /></template>
