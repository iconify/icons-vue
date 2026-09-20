<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r07kyrbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r07kyrbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circular-pill-and-capsule-pill-above-outstretched-hand" /></template>
