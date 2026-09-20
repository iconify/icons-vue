<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tya28ccex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tya28ccex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid-eraser-filled" /></template>
