<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0gxjcbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0gxjcbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flame" /></template>
