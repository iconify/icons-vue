<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak2lr7bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="ak2lr7bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:file-add" /></template>
