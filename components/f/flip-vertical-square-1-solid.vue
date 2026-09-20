<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv56qmxvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lv56qmxvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flip-vertical-square-1-solid" /></template>
