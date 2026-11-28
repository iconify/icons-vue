<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poya7oh9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poya7oh9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:door-lock" /></template>
