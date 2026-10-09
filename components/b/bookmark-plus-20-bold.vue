<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x07oq7k1t.css';
import '../../css/h/h02a5vbhw.css';
import '../../css/b/bz2g1kbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x07oq7k1t"/><path class="h02a5vbhw"/><path class="bz2g1kbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-plus-20-bold" /></template>
