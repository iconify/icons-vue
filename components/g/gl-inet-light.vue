<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me-ycib7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="me-ycib7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gl-inet-light" /></template>
