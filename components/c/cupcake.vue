<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uen46bb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uen46bb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:cupcake" /></template>
