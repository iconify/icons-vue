<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhrif_b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yhrif_b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airplane-disabled" /></template>
