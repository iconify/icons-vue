<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey-ar0bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":644};
const content = `<path class="ey-ar0bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:alignright" /></template>
