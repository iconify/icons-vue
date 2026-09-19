<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k09yz1bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k09yz1bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-1-bold" /></template>
