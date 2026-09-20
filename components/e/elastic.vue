<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg0pp0bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0pp0bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:elastic" /></template>
