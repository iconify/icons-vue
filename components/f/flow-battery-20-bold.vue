<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqlynnpbk.css';
import '../../css/l/l314gk7pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hqlynnpbk"/><path class="l314gk7pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flow-battery-20-bold" /></template>
