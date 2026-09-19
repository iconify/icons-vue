<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhvj11uls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rhvj11uls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-play" /></template>
