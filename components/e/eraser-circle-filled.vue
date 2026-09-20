<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l693y2see.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l693y2see"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eraser-circle-filled" /></template>
