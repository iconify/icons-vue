<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6gucccvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6gucccvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cable-car" /></template>
