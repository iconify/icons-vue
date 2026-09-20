<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jso1dfb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jso1dfb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:camera-solid" /></template>
