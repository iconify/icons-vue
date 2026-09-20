<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg0rbf0zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg0rbf0zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-upload" /></template>
