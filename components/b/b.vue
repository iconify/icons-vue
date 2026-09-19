<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohg5shbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ohg5shbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:b" /></template>
