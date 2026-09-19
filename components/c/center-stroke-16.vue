<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc3srnbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cc3srnbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:center-stroke-16" /></template>
