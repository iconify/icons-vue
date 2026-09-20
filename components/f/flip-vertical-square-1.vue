<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4mpeygnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4mpeygnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flip-vertical-square-1" /></template>
