<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de--p5bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de--p5bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-minimalistic-bold" /></template>
