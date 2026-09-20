<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw0azo2px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uw0azo2px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:barkeep-dark" /></template>
