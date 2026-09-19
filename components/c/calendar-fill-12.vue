<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy6bk_bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uy6bk_bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:calendar-fill-12" /></template>
