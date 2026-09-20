<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5n__acci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5n__acci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cert-manager-light" /></template>
