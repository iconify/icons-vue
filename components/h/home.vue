<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdzws5_nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzws5_nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:home" /></template>
