<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiabuuwes.css';
import '../../css/h/hpxwjdbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fiabuuwes"/><path class="hpxwjdbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:data-pipeline-20" /></template>
