<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tw6t4sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9tw6t4sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:debian-light" /></template>
