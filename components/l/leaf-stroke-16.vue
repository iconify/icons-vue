<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0eold8jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0eold8jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:leaf-stroke-16" /></template>
