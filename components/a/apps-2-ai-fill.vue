<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qylr5_b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qylr5_b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-2-ai-fill" /></template>
