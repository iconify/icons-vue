<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqjnyrgsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zqjnyrgsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hands-asl-interpreting" /></template>
