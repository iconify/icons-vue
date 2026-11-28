<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oedbzrzfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oedbzrzfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:home-minus" /></template>
