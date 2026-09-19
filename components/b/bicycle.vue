<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg3j76tts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rg3j76tts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bicycle" /></template>
