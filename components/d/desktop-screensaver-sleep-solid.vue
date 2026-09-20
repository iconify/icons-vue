<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7gu3tban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7gu3tban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:desktop-screensaver-sleep-solid" /></template>
