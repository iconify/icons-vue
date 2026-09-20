<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx9y36b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx9y36b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-ai-24" /></template>
