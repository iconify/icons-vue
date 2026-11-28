<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_15s1bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_15s1bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flame-x" /></template>
