<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxptxzbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxptxzbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hockey" /></template>
