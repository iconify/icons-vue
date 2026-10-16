<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh2hmebrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lh2hmebrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-mix-20" /></template>
