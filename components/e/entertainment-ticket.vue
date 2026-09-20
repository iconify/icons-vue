<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0m4hyiak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w0m4hyiak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:entertainment-ticket" /></template>
