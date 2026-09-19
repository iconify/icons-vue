<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z65jc1l0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z65jc1l0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-2-fill" /></template>
