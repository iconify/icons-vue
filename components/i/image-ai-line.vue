<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfeqwxbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfeqwxbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-ai-line" /></template>
