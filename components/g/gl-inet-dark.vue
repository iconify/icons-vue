<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ds4ubva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9ds4ubva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gl-inet-dark" /></template>
