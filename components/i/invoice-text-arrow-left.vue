<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0q8-_4mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0q8-_4mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-arrow-left" /></template>
