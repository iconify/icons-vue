<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmrvtc9go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmrvtc9go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-ai-line" /></template>
