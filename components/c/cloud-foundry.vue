<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjcsbubrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjcsbubrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cloud-foundry" /></template>
