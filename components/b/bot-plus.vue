<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa6fe6usc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa6fe6usc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bot-plus" /></template>
