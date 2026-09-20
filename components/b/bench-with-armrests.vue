<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbkgs1b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nbkgs1b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bench-with-armrests" /></template>
