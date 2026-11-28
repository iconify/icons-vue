<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c43uy5bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c43uy5bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:group-bold" /></template>
