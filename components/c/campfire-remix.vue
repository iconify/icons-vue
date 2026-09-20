<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjvm70twi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tjvm70twi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:campfire-remix" /></template>
