<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_3_dhjxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3_dhjxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-delete" /></template>
