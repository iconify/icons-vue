<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnhd3fn8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnhd3fn8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-ai-fill" /></template>
