<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7yq17xdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n7yq17xdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-xml-fill" /></template>
