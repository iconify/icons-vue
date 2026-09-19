<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dthqiw2vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dthqiw2vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bela" /></template>
