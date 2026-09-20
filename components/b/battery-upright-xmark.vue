<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk4rufb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nk4rufb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-xmark" /></template>
