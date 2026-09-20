<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivl6uulsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ivl6uulsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eraser" /></template>
