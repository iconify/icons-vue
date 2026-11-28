<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u61-btb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u61-btb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:layers-minus" /></template>
