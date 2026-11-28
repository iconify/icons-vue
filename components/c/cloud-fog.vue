<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7av1s0fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7av1s0fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-fog" /></template>
