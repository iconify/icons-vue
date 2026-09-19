<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij-b_giyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij-b_giyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cocktail" /></template>
