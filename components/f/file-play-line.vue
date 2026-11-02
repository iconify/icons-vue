<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyhup04vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyhup04vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-play-line" /></template>
