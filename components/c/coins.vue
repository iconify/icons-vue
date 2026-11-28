<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-3n7myzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-3n7myzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coins" /></template>
