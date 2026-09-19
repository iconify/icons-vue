<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-5uqbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jr-5uqbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-right-arrow-left" /></template>
