<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu72g8qcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cu72g8qcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-slash" /></template>
