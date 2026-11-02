<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvocr5bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvocr5bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:document-line" /></template>
