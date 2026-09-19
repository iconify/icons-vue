<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r439nr-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="r439nr-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:birdhouse" /></template>
