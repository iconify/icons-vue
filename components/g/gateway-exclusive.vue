<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm02tab2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wm02tab2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gateway-exclusive" /></template>
