<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zib0qbour.css';
import '../../css/k/k5pr-v-xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zib0qbour"/><path class="k5pr-v-xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-right-stroke-square" /></template>
