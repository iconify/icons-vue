<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp6bi2wym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp6bi2wym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-down-circle-line" /></template>
