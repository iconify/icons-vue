<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-yd0b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie-yd0b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:component-solid" /></template>
