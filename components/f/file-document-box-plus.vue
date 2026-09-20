<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuk17vbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuk17vbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-box-plus" /></template>
