<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-hvr0byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="d-hvr0byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:dryad-square" /></template>
