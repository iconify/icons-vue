<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0vpinqjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0vpinqjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:control-text-button" /></template>
