<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgjgpabzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgjgpabzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bluetooth" /></template>
