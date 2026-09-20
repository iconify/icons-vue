<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve_g31b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve_g31b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon-slice-5" /></template>
