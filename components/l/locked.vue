<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_br1i1fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k_br1i1fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:locked" /></template>
