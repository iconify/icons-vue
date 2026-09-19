<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhsxpmunn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dhsxpmunn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-z-a" /></template>
