<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mec9fr0sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mec9fr0sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:magnet" /></template>
