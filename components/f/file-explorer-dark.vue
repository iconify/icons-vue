<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4v7vnbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4v7vnbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-explorer-dark" /></template>
