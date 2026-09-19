<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpvptsbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fpvptsbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cog-8-tooth-16-solid" /></template>
