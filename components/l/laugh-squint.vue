<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa0resxcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qa0resxcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:laugh-squint" /></template>
