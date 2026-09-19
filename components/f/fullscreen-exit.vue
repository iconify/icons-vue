<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imt344b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="imt344b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:fullscreen-exit" /></template>
