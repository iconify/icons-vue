<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg7v921kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg7v921kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ai-generate-3d-fill" /></template>
