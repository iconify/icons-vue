<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u25liwb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u25liwb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:filter" /></template>
