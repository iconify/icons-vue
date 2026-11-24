<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-jafa0z.css';
import '../../css/e/e9d8alb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-jafa0z"/><path class="e9d8alb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-download-filled" /></template>
