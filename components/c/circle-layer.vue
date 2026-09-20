<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz7sr6bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz7sr6bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:circle-layer" /></template>
