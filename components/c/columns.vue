<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8hymc3pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8hymc3pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:columns" /></template>
