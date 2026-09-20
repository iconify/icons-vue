<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clrdxwbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clrdxwbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cactus-line" /></template>
