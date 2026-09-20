<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlqboo-0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dlqboo-0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:highlight" /></template>
