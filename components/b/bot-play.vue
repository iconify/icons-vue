<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-tn56vsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-tn56vsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bot-play" /></template>
