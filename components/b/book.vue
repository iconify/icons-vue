<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv4vo1bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wv4vo1bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:book" /></template>
