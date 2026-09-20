<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo6cm4bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo6cm4bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-2-fill" /></template>
