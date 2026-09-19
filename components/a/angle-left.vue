<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2cgykpmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="u2cgykpmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angle-left" /></template>
