<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi3uv14or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oi3uv14or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:closed-caption-filled" /></template>
