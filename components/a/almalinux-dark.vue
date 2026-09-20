<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3x_g1b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3x_g1b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:almalinux-dark" /></template>
