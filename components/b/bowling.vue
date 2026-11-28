<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umn1iwb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umn1iwb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bowling" /></template>
