<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib4xsfe2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib4xsfe2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:adjust" /></template>
