<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnnd0yb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dnnd0yb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:butcher-14" /></template>
