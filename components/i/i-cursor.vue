<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5eqpqbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="m5eqpqbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:i-cursor" /></template>
