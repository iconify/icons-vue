<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2q0fmb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y2q0fmb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:gift" /></template>
