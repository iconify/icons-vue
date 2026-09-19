<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wte_qbcjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="wte_qbcjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:braille" /></template>
