<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lowqi3bit.css';
import '../../css/n/nm733ibre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lowqi3bit"/><path class="nm733ibre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:business-coaching-whistle" /></template>
