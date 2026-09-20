<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm7nx75dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pm7nx75dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-move" /></template>
