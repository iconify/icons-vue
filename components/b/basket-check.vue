<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxh-a_buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxh-a_buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:basket-check" /></template>
