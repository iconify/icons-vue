<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox824z_gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ox824z_gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:galaxy-2-remix" /></template>
