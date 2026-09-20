<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzuim_b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uzuim_b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:adjust" /></template>
