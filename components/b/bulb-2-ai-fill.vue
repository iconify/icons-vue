<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d204npb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d204npb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-2-ai-fill" /></template>
