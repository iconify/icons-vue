<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rujup72zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rujup72zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-warning-fill" /></template>
