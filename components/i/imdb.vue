<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2j9s7bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p2j9s7bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:imdb" /></template>
