<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb1thxfbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="sb1thxfbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cc-diners-club" /></template>
