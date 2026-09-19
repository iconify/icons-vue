<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctf8m1brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ctf8m1brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:magnet" /></template>
