<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_j3evu8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_j3evu8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-plus-solid" /></template>
