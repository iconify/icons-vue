<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2o6fw_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex2o6fw_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-3-ai-line" /></template>
