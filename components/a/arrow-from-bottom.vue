<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1j1_gbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1j1_gbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:arrow-from-bottom" /></template>
