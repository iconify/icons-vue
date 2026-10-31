<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buwf06b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buwf06b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-close-round" /></template>
