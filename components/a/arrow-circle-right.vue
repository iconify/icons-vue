<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fealj4bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fealj4bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-circle-right" /></template>
