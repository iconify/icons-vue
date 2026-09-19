<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8jcolbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u8jcolbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:chevron-left" /></template>
