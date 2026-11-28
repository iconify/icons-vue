<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkeux50xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkeux50xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:crosshair-solid" /></template>
