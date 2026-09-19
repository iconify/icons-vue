<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de2nv-xgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="de2nv-xgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cloud-with-snow" /></template>
