<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_w4j6r0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_w4j6r0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:floating-dust-line" /></template>
