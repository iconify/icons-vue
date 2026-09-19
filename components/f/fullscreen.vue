<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y97f60bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y97f60bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:fullscreen" /></template>
