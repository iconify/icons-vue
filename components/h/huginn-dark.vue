<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhx0_eg3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhx0_eg3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:huginn-dark" /></template>
