<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_3nitkdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p_3nitkdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:cog" /></template>
