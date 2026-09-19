<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp7kilijg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp7kilijg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-voice-generator" /></template>
