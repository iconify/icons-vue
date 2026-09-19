<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoemicr0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="hoemicr0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bold" /></template>
