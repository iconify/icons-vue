<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syb3c432m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="syb3c432m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cam-track" /></template>
