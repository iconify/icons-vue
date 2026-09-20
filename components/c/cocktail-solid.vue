<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i65-tqbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i65-tqbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cocktail-solid" /></template>
