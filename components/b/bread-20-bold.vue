<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ndo13-j.css';
import '../../css/t/tyb8w2bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o1ndo13-j"/><path class="tyb8w2bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bread-20-bold" /></template>
