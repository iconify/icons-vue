<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc1x0_-rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc1x0_-rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clubs-line" /></template>
