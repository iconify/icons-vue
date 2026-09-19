<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4gcyob3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="k4gcyob3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-square-right" /></template>
