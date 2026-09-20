<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i31-vfb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i31-vfb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-center-solid" /></template>
