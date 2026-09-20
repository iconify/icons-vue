<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb6o74bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb6o74bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-ai-2-fill" /></template>
