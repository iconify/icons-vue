<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj73_9b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj73_9b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-2-fill" /></template>
