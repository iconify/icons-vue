<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9kcm970w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9kcm970w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:draw-io-light" /></template>
