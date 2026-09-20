<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruxc2r0ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ruxc2r0ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-news-dark" /></template>
