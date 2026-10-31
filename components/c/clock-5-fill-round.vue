<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azmgfgb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azmgfgb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-5-fill-round" /></template>
