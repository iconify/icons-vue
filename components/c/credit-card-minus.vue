<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0xf8_tbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0xf8_tbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:credit-card-minus" /></template>
