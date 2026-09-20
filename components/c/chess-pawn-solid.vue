<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rca1_3t3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rca1_3t3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chess-pawn-solid" /></template>
