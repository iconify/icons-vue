<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv78f6y5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv78f6y5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ampersands-fill" /></template>
