<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u05b4hbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u05b4hbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-fill-round" /></template>
