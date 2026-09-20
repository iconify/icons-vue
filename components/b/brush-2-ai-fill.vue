<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf-0_1bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf-0_1bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-2-ai-fill" /></template>
