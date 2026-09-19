<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-g__d1hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-g__d1hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:glass-martini" /></template>
