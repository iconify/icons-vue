<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulk4puohh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ulk4puohh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-return-left" /></template>
