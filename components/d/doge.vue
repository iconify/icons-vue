<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5cd--b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u5cd--b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:doge" /></template>
