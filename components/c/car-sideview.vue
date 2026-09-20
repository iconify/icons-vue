<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gok6tprfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gok6tprfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:car-sideview" /></template>
