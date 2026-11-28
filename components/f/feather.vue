<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwg4es6gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwg4es6gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:feather" /></template>
