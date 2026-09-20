<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se0wmr1vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="se0wmr1vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horse-head-wearing-bridle" /></template>
