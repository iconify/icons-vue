<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv2vcxszl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv2vcxszl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-left-fill-round" /></template>
