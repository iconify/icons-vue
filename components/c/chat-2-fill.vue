<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-axlvifi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-axlvifi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-2-fill" /></template>
