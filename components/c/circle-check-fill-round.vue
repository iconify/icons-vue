<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uizmpkbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uizmpkbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-check-fill-round" /></template>
