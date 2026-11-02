<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nifkghh6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nifkghh6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-new-fill" /></template>
