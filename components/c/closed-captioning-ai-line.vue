<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc6clwbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc6clwbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:closed-captioning-ai-line" /></template>
