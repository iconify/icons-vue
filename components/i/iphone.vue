<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbo7vsg8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fbo7vsg8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:iphone" /></template>
