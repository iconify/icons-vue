<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ottczzbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ottczzbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-up" /></template>
