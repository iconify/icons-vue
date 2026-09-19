<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8ey5rnuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a8ey5rnuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:boot-volume" /></template>
