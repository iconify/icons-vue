<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8oldcbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q8oldcbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:huc" /></template>
