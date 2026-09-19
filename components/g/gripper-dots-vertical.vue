<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/injpc11dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="injpc11dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:gripper-dots-vertical" /></template>
