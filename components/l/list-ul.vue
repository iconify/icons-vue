<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0asqjhxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0asqjhxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:list-ul" /></template>
