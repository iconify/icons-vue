<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx_t18ycs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx_t18ycs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:agent-fill-round" /></template>
