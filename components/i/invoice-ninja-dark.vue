<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck-49pk6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck-49pk6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoice-ninja-dark" /></template>
