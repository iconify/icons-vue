<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3np0yb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3np0yb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-square-fill-20" /></template>
