<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3mtcrbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w3mtcrbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-move-horizontal-remix" /></template>
