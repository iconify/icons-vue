<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6y3u4-gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6y3u4-gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:boat" /></template>
