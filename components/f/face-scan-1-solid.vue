<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyb9v64yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dyb9v64yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:face-scan-1-solid" /></template>
