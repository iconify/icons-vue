<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tro9njgej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tro9njgej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:favro" /></template>
