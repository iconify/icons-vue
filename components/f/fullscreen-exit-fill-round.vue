<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzzhhh4ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzzhhh4ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-exit-fill-round" /></template>
