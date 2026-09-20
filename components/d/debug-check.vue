<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we2mvzuyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we2mvzuyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:debug-check" /></template>
