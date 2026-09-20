<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/une53x_rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="une53x_rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:import4" /></template>
