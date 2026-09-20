<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uppu-lcaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uppu-lcaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:brandfetch" /></template>
