<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3x4e39zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y3x4e39zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-box-gabled-building-with-chimney-and-door" /></template>
