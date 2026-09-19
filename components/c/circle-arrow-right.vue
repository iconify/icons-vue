<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvkwf439u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dvkwf439u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-arrow-right" /></template>
