<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpt8mwb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpt8mwb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:currency-solid" /></template>
