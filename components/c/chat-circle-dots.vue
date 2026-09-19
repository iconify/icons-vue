<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpuf8n8va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpuf8n8va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-dots" /></template>
