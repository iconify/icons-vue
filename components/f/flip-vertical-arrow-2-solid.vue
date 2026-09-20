<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyf8izpjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iyf8izpjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flip-vertical-arrow-2-solid" /></template>
