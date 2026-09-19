<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz6gwxb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jz6gwxb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:high-speed-train" /></template>
