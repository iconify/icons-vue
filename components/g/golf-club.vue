<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuv29vqrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tuv29vqrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:golf-club" /></template>
