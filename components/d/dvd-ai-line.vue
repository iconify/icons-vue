<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw2k2kb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw2k2kb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dvd-ai-line" /></template>
