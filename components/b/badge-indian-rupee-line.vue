<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do582sswp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do582sswp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-indian-rupee-line" /></template>
