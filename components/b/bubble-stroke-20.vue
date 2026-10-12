<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khwlhgbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="khwlhgbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-stroke-20" /></template>
