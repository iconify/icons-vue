<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtt9_ab8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtt9_ab8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ai-agent-line" /></template>
