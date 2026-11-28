<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2d838bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2d838bfi primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:filter-duotone" /></template>
