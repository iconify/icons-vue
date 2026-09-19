<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tin5cxlxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tin5cxlxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-minus" /></template>
