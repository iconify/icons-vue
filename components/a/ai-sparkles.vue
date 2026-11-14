<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6o3toent.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6o3toent"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-sparkles" /></template>
