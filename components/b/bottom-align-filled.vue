<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl6o323gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jl6o323gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bottom-align-filled" /></template>
