<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yurwjibje.css';
import '../../css/v/vqsj2lnqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yurwjibje"/><path class="vqsj2lnqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:business-workflow-merge-2" /></template>
