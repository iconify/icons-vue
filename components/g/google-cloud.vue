<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd6r2njpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6r2njpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:google-cloud" /></template>
