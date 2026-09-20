<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv8k65bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uv8k65bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:dam-11" /></template>
