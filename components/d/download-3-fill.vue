<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni-8--job.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni-8--job"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-3-fill" /></template>
