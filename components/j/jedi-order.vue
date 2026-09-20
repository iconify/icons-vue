<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0-3p01nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u0-3p01nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:jedi-order" /></template>
