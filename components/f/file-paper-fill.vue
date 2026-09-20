<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf6rbr4fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6rbr4fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-paper-fill" /></template>
