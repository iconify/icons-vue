<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olkmp-6tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olkmp-6tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:landscape-ai-fill" /></template>
