<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzi_4nscr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzi_4nscr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-acrobat" /></template>
