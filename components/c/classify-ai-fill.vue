<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na5768bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na5768bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-ai-fill" /></template>
