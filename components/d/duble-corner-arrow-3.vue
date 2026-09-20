<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahy-3rbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahy-3rbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:duble-corner-arrow-3" /></template>
