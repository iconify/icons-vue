<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai-ap6q9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai-ap6q9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cat-filled" /></template>
