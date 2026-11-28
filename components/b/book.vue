<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiqk-gcqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiqk-gcqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book" /></template>
