<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7o185bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7o185bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:airplane-alt-line" /></template>
