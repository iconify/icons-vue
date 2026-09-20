<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0hot5bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0hot5bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:help-rhombus" /></template>
