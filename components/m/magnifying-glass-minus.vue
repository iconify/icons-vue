<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9oj01ydv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9oj01ydv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:magnifying-glass-minus" /></template>
