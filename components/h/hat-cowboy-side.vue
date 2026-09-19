<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtjs7gb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xtjs7gb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hat-cowboy-side" /></template>
