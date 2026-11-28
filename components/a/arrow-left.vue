<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6rg17h4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rg17h4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-left" /></template>
