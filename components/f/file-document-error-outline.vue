<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwngp28av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwngp28av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-error-outline" /></template>
