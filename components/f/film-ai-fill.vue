<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ksueiwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ksueiwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:film-ai-fill" /></template>
