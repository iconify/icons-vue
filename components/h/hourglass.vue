<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2908egb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij2908egb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:hourglass" /></template>
