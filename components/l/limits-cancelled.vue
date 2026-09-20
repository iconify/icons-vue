<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khxp_lblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="khxp_lblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:limits-cancelled" /></template>
