<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt5jl0bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yt5jl0bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chart-bar-square-16-solid" /></template>
