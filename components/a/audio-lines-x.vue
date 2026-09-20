<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjym-4_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjym-4_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:audio-lines-x" /></template>
