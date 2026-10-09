<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7xl99bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o7xl99bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-left-20-bold" /></template>
