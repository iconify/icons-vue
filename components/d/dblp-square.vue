<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc6clzbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tc6clzbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:dblp-square" /></template>
