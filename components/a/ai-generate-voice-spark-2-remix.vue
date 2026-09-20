<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5gcds8nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5gcds8nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-generate-voice-spark-2-remix" /></template>
