<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx8h7_bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tx8h7_bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:back-camera-1-remix" /></template>
