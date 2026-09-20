<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnrsqqwlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fnrsqqwlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:deno-light" /></template>
