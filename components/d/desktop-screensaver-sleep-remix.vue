<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnhm3dmjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnhm3dmjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:desktop-screensaver-sleep-remix" /></template>
