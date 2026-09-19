<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2y_09oek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2y_09oek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-right-stroke" /></template>
