<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x08h1abni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x08h1abni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:laptop-camera-solid" /></template>
