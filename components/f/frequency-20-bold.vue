<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixcl-v7ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ixcl-v7ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frequency-20-bold" /></template>
