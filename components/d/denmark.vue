<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42v9bvgu.css';
import '../../css/z/z3o5mebhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="k42v9bvgu"/><path class="z3o5mebhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:denmark" /></template>
