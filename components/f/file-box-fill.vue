<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilmcf-bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilmcf-bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-box-fill" /></template>
