<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7nn73bmg.css';
import '../../css/u/ukh6i7bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w7nn73bmg"/><path class="ukh6i7bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jaco-dark" /></template>
