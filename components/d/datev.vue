<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po2328bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po2328bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:datev" /></template>
