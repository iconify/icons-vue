<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj1tirh6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pj1tirh6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crates-in-rectangle-outline-under-arrow-up-beside-arrow-down" /></template>
