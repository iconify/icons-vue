<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf0ka5mro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vf0ka5mro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:forward" /></template>
