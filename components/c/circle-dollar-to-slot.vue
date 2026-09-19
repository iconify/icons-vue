<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny9xkfbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ny9xkfbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-dollar-to-slot" /></template>
