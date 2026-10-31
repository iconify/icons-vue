<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swav2ec8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swav2ec8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-from-line-fill-round" /></template>
