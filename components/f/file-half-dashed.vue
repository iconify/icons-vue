<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg3spjb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="eg3spjb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-half-dashed" /></template>
