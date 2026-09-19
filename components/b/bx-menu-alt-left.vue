<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg28z8byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg28z8byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-menu-alt-left" /></template>
