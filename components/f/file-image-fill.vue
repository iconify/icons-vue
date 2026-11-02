<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khas7qbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khas7qbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-image-fill" /></template>
