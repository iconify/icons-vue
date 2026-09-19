<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utvgn6bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="utvgn6bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:codepen" /></template>
