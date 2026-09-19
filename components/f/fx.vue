<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj_bjqbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj_bjqbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fx" /></template>
