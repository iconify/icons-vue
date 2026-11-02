<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7m6orn2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7m6orn2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-exit-2-line" /></template>
