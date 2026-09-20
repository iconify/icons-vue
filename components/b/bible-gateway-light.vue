<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cywfknbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cywfknbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bible-gateway-light" /></template>
