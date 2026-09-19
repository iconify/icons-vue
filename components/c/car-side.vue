<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt-nmm86o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="yt-nmm86o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:car-side" /></template>
