<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw9awtb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dw9awtb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-3-fill" /></template>
