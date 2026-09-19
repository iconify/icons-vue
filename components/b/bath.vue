<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y23bmpb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y23bmpb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bath" /></template>
