<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5ytpbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rh5ytpbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-cancelled" /></template>
