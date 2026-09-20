<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km0j_jb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="km0j_jb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:arrow-thin-down" /></template>
