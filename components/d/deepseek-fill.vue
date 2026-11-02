<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1d99dgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu1d99dgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:deepseek-fill" /></template>
