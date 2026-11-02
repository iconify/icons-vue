<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvb0gpb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvb0gpb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-bottom-fill" /></template>
