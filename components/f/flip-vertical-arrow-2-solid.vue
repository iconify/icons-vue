<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvtsq_bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvtsq_bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flip-vertical-arrow-2-solid" /></template>
