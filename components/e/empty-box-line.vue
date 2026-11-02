<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8i-qwj9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8i-qwj9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:empty-box-line" /></template>
