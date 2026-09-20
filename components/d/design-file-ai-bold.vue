<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjplskbvx.css';
import '../../css/s/s-s3ptbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjplskbvx"/><path class="s-s3ptbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-file-ai-bold" /></template>
