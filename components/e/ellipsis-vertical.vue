<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfxatyb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfxatyb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:ellipsis-vertical" /></template>
