<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7qpb49an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7qpb49an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-coffee-alt" /></template>
