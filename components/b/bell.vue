<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh54mgb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xh54mgb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bell" /></template>
