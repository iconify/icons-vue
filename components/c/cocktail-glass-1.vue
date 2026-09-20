<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkow5mkrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkow5mkrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cocktail-glass-1" /></template>
