<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbrj4gkkb.css';
import '../../css/y/ytbt4-b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbrj4gkkb"/><path class="ytbt4-b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:clone" /></template>
