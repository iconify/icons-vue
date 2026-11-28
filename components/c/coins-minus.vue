<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip8rx8bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip8rx8bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coins-minus" /></template>
