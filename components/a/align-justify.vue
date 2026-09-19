<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh5j6-3xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="sh5j6-3xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:align-justify" /></template>
