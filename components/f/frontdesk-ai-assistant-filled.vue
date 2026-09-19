<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8sv8wb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8sv8wb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:frontdesk-ai-assistant-filled" /></template>
