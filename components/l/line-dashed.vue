<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1eig5b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="y1eig5b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:line-dashed" /></template>
