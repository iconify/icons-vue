<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy7sa5acr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zy7sa5acr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cloud" /></template>
