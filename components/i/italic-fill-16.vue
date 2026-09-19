<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf8o0cciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf8o0cciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:italic-fill-16" /></template>
