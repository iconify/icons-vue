<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c054m9cuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c054m9cuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dislike" /></template>
