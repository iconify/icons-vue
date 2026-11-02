<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn8g1ddly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn8g1ddly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grok-2-fill" /></template>
