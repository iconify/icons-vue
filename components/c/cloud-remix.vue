<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4btlvb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d4btlvb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-remix" /></template>
