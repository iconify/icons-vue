<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1b3pxbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i1b3pxbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-grin-tongue-squint" /></template>
