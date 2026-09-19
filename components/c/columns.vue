<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhl75kbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yhl75kbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:columns" /></template>
