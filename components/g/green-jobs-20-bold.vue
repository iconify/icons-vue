<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh0-6objo.css';
import '../../css/u/u5hzo-bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bh0-6objo"/><path class="u5hzo-bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-jobs-20-bold" /></template>
