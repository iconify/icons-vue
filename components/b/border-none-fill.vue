<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc4u2xbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mc4u2xbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-none-fill" /></template>
