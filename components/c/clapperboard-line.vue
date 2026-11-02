<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dev8gqqqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dev8gqqqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clapperboard-line" /></template>
