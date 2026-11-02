<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f06gkkbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f06gkkbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:headphone-line" /></template>
