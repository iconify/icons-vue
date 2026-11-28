<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv8x3ccsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv8x3ccsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-solid" /></template>
