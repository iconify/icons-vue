<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_-ow0b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u_-ow0b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:doc" /></template>
