<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf2ng0bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf2ng0bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:astronomy-planet-saturn-1-bold" /></template>
