<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy-n0abja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yy-n0abja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coconuts" /></template>
