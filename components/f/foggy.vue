<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0mohjmfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0mohjmfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:foggy" /></template>
