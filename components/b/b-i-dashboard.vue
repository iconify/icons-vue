<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy7m0b3bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uy7m0b3bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:b-i-dashboard" /></template>
