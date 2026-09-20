<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdorq249g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdorq249g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-multiple" /></template>
