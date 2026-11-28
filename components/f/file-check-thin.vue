<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on15oyn-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="on15oyn-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-check-thin" /></template>
