<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk8zpy4cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk8zpy4cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-big-up-dash" /></template>
