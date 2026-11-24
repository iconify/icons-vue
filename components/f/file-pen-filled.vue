<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq7fbvbpx.css';
import '../../css/p/pj3mk0brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq7fbvbpx"/><path class="pj3mk0brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-pen-filled" /></template>
