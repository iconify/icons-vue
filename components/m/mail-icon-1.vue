<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpy23lbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpy23lbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mail-icon-1" /></template>
