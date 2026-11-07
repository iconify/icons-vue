<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m92zv-bjj.css';
import '../../css/d/dmh6kqbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m92zv-bjj"/><path clip-rule="evenodd" class="dmh6kqbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-off-bold" /></template>
