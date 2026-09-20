<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trz3lobaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trz3lobaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codeproject" /></template>
