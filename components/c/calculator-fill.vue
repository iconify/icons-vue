<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu4v_kdxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu4v_kdxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calculator-fill" /></template>
