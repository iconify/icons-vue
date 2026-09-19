<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz0y5abce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz0y5abce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-home-circle" /></template>
