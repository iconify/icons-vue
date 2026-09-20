<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okt830xak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="okt830xak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:inaturalist-square" /></template>
