<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po3vl1blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po3vl1blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dtube" /></template>
