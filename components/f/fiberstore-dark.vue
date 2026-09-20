<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkfx91bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qkfx91bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fiberstore-dark" /></template>
