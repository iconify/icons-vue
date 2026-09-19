<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8nj21w8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c8nj21w8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:code-branch" /></template>
