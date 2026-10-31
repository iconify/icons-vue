<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_uxf-nhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_uxf-nhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-half-round" /></template>
