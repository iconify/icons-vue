<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n42_rfpae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n42_rfpae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:build-run" /></template>
