<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjjjb_bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjjjb_bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-upload-line" /></template>
