<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjo48szol.css';
import '../../css/a/a5r52wb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjo48szol"/><path class="a5r52wb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:buildings-1" /></template>
