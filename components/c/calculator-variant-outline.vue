<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx24dwzoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx24dwzoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calculator-variant-outline" /></template>
