<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_f4aibym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_f4aibym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-square" /></template>
