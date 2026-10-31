<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1_05pxtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1_05pxtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-right-down-duotone-round" /></template>
