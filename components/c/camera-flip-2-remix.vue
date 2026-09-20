<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyhhs_6ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qyhhs_6ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:camera-flip-2-remix" /></template>
