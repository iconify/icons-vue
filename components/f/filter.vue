<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udes82bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="udes82bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:filter" /></template>
