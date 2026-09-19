<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tom5xu4iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="tom5xu4iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cursor" /></template>
