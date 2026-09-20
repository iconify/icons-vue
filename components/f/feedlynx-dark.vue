<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2nbv-b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2nbv-b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedlynx-dark" /></template>
