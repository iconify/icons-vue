<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpu0h8btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jpu0h8btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-bar-left" /></template>
