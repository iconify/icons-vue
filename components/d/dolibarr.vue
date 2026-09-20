<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct8vf37rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8vf37rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dolibarr" /></template>
