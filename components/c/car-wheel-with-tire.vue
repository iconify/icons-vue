<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1wohmrfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h1wohmrfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-wheel-with-tire" /></template>
