<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugtg92bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":189,"height":52};
const content = `<path class="ugtg92bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lunit" /></template>
