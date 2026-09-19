<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex3o1inzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex3o1inzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:grid-round" /></template>
