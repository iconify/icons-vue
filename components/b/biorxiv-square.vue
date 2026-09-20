<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahns1ub3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ahns1ub3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:biorxiv-square" /></template>
