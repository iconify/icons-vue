<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tga5ydbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tga5ydbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:iot" /></template>
