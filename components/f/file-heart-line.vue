<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-v7ou0hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-v7ou0hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-heart-line" /></template>
