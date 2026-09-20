<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-42yhbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s-42yhbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:isosceles-trapezoid-tall-up" /></template>
