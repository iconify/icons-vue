<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1xjp8bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1xjp8bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-upload-line" /></template>
