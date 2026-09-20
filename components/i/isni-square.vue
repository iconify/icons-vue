<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u83vykqso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u83vykqso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:isni-square" /></template>
