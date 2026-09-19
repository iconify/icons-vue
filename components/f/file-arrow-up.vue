<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucnqb3dtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ucnqb3dtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-arrow-up" /></template>
