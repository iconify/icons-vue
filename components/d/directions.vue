<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2d-zbcwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q2d-zbcwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:directions" /></template>
