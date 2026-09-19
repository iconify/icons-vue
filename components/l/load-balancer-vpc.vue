<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_2gxssyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u_2gxssyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-vpc" /></template>
