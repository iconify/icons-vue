<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzaw-obto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="mzaw-obto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:back" /></template>
