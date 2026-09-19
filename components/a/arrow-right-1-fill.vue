<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz7z-qbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hz7z-qbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-1-fill" /></template>
