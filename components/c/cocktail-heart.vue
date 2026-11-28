<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnt9jgwzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnt9jgwzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cocktail-heart" /></template>
