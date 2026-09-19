<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6dg5j3rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="s6dg5j3rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:glass" /></template>
