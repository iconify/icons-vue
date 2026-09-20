<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd-wbsxqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-wbsxqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-terminal-bold" /></template>
