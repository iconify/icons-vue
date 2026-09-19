<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0kbwcbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":644};
const content = `<path class="c0kbwcbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:alignadjust" /></template>
