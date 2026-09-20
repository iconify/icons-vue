<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0dw43uro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0dw43uro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:charles" /></template>
