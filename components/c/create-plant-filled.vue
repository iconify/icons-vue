<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgm0cybgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wgm0cybgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:create-plant-filled" /></template>
