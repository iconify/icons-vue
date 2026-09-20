<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb811w4oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb811w4oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-lucene" /></template>
