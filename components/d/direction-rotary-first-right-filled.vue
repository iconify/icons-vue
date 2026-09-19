<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6qay1xjw.css';
import '../../css/q/qutfy0qah.css';
import '../../css/y/yj4j86lvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="s6qay1xjw"/><path class="qutfy0qah"/><path class="yj4j86lvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-rotary-first-right-filled" /></template>
