<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6k1i1bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6k1i1bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-google" /></template>
