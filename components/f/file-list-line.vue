<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5j3nrbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5j3nrbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-list-line" /></template>
