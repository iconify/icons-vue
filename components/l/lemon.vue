<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxzr4tbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxzr4tbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lemon" /></template>
