<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mosw6vb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mosw6vb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dweb" /></template>
