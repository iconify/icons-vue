<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z14k1koii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z14k1koii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-up-from-ground-water" /></template>
