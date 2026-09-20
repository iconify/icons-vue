<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rec4skbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rec4skbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-sound" /></template>
