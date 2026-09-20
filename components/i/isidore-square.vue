<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fst_4tbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fst_4tbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:isidore-square" /></template>
