<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpmydebry.css';
import '../../css/k/kgk78cbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpmydebry"/><path class="kgk78cbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:coin-insert" /></template>
