<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt9muxegx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt9muxegx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:card-layout" /></template>
