<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjfkx4bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfkx4bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:flip-horizontal" /></template>
