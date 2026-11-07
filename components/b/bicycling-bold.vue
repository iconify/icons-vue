<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6gx6-b_c.css';
import '../../css/f/fbvycxxai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6gx6-b_c"/><path clip-rule="evenodd" class="fbvycxxai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-bold" /></template>
