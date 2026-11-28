<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shf32-ouq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shf32-ouq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cone" /></template>
