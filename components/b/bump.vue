<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yivp0jbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yivp0jbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bump" /></template>
