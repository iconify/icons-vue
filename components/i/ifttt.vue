<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7bt9bcab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7bt9bcab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ifttt" /></template>
