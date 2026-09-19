<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_w53ebqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_w53ebqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-battery" /></template>
