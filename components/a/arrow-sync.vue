<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcli11bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcli11bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-sync" /></template>
