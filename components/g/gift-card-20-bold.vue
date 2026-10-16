<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6dd8jb9u.css';
import '../../css/f/fsk9461bq.css';
import '../../css/n/nf5sa9buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l6dd8jb9u"/><path class="fsk9461bq"/><path class="nf5sa9buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gift-card-20-bold" /></template>
