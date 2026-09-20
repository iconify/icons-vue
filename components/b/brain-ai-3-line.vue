<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knlvkn1xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knlvkn1xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-ai-3-line" /></template>
