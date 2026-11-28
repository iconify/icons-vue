<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plng_wb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plng_wb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-off-page" /></template>
