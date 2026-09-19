<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-9fyzgba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":646};
const content = `<path class="r-9fyzgba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:grayscale" /></template>
