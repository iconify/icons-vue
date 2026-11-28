<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnom45bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnom45bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:jump-rope" /></template>
