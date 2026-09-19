<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znr2oyb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="znr2oyb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ht" /></template>
