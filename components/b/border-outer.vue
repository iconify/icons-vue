<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lprujtblw.css';
import '../../css/q/q33pllwot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lprujtblw"/><path class="q33pllwot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-outer" /></template>
