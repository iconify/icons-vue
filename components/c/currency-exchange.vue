<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pll1c7hqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pll1c7hqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:currency-exchange" /></template>
