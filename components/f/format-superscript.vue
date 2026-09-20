<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvosu6bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvosu6bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-superscript" /></template>
