<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djefxr29r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djefxr29r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hat-wizard" /></template>
