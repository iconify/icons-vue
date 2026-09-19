<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgf8n7bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vgf8n7bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:api-1" /></template>
