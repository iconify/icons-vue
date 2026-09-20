<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce6gxvdaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ce6gxvdaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:argon-theme-light" /></template>
