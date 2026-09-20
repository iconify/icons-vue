<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spcaiwx2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spcaiwx2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:help" /></template>
