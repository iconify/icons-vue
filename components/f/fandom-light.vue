<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eekg15-bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eekg15-bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fandom-light" /></template>
