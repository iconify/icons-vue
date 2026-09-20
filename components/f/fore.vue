<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlxa5ophx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlxa5ophx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fore" /></template>
