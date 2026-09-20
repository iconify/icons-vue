<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ave5p0b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ave5p0b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-happy-line" /></template>
