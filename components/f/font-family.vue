<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj_sf5b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj_sf5b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:font-family" /></template>
