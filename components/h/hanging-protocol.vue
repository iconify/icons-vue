<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzul08b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fzul08b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hanging-protocol" /></template>
