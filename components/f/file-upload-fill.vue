<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/indfb2voo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="indfb2voo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-upload-fill" /></template>
