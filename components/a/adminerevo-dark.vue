<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km3avxbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="km3avxbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adminerevo-dark" /></template>
