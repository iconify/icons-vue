<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqxnqdk_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqxnqdk_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-image-1-filled" /></template>
