<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj7tdsdto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cj7tdsdto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:broom" /></template>
