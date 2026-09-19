<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q41euobio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q41euobio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:connectdevelop" /></template>
