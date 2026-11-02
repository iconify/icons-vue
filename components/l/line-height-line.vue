<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkxxj0bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkxxj0bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-height-line" /></template>
