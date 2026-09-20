<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_q3o-bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="h_q3o-bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:close" /></template>
