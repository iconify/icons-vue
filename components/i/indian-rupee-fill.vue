<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8hz16hbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8hz16hbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:indian-rupee-fill" /></template>
