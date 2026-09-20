<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hux14ll4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hux14ll4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:expand-left" /></template>
