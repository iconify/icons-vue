<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1-d3eqbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-d3eqbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-down-short-duotone" /></template>
