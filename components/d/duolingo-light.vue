<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex0pby3hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ex0pby3hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duolingo-light" /></template>
