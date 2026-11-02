<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3wm5xxdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3wm5xxdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-2-off-line" /></template>
