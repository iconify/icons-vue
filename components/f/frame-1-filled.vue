<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3o_lrcqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3o_lrcqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:frame-1-filled" /></template>
